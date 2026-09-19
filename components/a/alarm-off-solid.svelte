<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clcsdocbl.css';
import '../../css/i/i7v4jn80w.css';
import '../../css/y/yzu76tbsx.css';
import '../../css/l/lm4-4zbuu.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clcsdocbl clr-i-solid clr-i-solid-path-1"/><path class="clr-i-solid clr-i-solid-path-2 i7v4jn80w"/><path class="clr-i-solid clr-i-solid-path-3 yzu76tbsx"/><path class="clr-i-solid clr-i-solid-path-4 lm4-4zbuu"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:alarm-off-solid" {...props}></Icon>
