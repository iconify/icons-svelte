<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_fyccblx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="g_fyccblx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:directions-sign-1-bold" {...props}></Icon>
