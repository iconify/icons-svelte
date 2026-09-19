<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyq7mlb0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="iyq7mlb0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:hand-holding-duo" {...props}></Icon>
