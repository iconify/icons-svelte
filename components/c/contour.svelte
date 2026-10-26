<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2q0x1bgc.css';
import '../../css/m/mw0gdnbgu.css';
import '../../css/e/eg_awvb4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":360,"height":360};
const content = `<path class="z2q0x1bgc"/><path class="mw0gdnbgu"/><path class="eg_awvb4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:contour" {...props}></Icon>
