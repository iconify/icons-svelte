<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngk232z-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ngk232z-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:four" {...props}></Icon>
