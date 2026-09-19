<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/id3vlyjng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="id3vlyjng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:heart-duo" {...props}></Icon>
