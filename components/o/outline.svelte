<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iis2jirxu.css';
import '../../css/f/fpfbwk8vq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iis2jirxu"/><path class="fpfbwk8vq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:outline" {...props}></Icon>
