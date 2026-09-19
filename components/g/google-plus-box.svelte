<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l27afibyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="l27afibyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:google-plus-box" {...props}></Icon>
