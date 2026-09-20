<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xc9f3eygk.css';
import '../../css/n/nw_fw7zya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="xc9f3eygk"/><path class="nw_fw7zya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:rightwards-hand-dark-skin-tone" {...props}></Icon>
