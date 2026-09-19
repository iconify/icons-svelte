<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yllu2lzhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":408,"height":384};
const content = `<path class="yllu2lzhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:playlist-audio" {...props}></Icon>
