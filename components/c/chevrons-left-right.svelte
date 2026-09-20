<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqxap_bvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pqxap_bvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:chevrons-left-right" {...props}></Icon>
