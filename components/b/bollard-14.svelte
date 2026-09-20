<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3375dbua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="w3375dbua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:bollard-14" {...props}></Icon>
