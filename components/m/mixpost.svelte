<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5kt4xr8s.css';
import '../../css/u/u_8a0r-bt.css';
import '../../css/z/zg70rbcur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g5kt4xr8s"/><path class="u_8a0r-bt"/><path class="zg70rbcur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mixpost" {...props}></Icon>
