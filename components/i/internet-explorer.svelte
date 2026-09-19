<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z69p_lzea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="z69p_lzea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:internet-explorer" {...props}></Icon>
