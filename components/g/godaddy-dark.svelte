<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dr7fluyjp.css';
import '../../css/k/k295tibms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":166,"height":34};
const content = `<path class="dr7fluyjp prefix__path-mobile"/><path class="k295tibms prefix__path-desktop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:godaddy-dark" {...props}></Icon>
