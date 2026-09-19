<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pktnifbwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="pktnifbwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:dollar-sign-bold" {...props}></Icon>
