<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcpug3b7d.css';
import '../../css/w/wvt4upzll.css';
import '../../css/r/rfmo84bve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fcpug3b7d"/><path class="wvt4upzll"/><path class="rfmo84bve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:chartupwardstrend" {...props}></Icon>
