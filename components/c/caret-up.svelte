<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-6mogbuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":216,"height":384};
const content = `<path class="z-6mogbuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:caret-up" {...props}></Icon>
