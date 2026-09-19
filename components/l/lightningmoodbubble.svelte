<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw4hi5b4t.css';
import '../../css/r/r5yjrccli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zw4hi5b4t"/><path class="r5yjrccli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:lightningmoodbubble" {...props}></Icon>
