<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ks_24obqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ks_24obqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:moon-star" {...props}></Icon>
