<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ryxl_tbum.css';
import '../../css/x/xka5jqons.css';
import '../../css/x/x7iitf4_b.css';
import '../../css/o/o8wlliifz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ryxl_tbum"/><path class="xka5jqons"/><path class="x7iitf4_b"/><path class="o8wlliifz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:qwik-wordmark" {...props}></Icon>
