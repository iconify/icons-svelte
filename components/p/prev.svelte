<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9xi539mx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="o9xi539mx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:prev" {...props}></Icon>
