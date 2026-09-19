<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie_odgy3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ie_odgy3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:i" {...props}></Icon>
