<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isaosi6ly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="isaosi6ly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:cross-christian-duo" {...props}></Icon>
