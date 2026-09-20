<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0874bc2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="n0874bc2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:move" {...props}></Icon>
