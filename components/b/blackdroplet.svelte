<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2kcvmbtw.css';
import '../../css/x/xnsfeobti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r2kcvmbtw"/><path class="xnsfeobti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:blackdroplet" {...props}></Icon>
