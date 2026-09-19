<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0b_ulbpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="s0b_ulbpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:activity-duo" {...props}></Icon>
