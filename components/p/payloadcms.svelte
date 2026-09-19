<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ux66g_b8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ux66g_b8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:payloadcms" {...props}></Icon>
