<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lz_zvrfmn.css';
import '../../css/u/uofvvkbxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lz_zvrfmn"/><path class="uofvvkbxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:music-microphone-off" {...props}></Icon>
