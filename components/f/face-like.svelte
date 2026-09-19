<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-4h1bclr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1664};
const content = `<path class="d-4h1bclr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:face-like" {...props}></Icon>
