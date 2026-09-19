<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvxjx97jd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="dvxjx97jd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:canoe-2-outline" {...props}></Icon>
