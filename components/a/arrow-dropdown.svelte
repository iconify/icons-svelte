<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-k_55dvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x-k_55dvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:arrow-dropdown" {...props}></Icon>
