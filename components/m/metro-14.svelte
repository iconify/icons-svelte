<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hex2xscoo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="hex2xscoo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:metro-14" {...props}></Icon>
