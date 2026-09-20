<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wr3evobfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wr3evobfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:hubspot" {...props}></Icon>
