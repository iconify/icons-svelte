<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynsy5g-wh.css';
import '../../css/w/wjoeyx4qk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ynsy5g-wh"/><path class="wjoeyx4qk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:multi-scrobbler" {...props}></Icon>
