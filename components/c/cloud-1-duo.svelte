<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktdy_3blv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ktdy_3blv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:cloud-1-duo" {...props}></Icon>
