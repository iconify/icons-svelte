<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ma43lzb_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ma43lzb_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:align-left" {...props}></Icon>
