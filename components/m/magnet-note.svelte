<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9k2y7bof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1664};
const content = `<path class="h9k2y7bof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:magnet-note" {...props}></Icon>
