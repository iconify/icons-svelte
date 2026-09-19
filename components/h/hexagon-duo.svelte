<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wf368b6bh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="wf368b6bh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:hexagon-duo" {...props}></Icon>
