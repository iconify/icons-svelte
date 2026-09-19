<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jttibe98e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="jttibe98e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:arrow-line-start-outline" {...props}></Icon>
