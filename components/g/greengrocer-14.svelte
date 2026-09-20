<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6ar3r9kx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="z6ar3r9kx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:greengrocer-14" {...props}></Icon>
