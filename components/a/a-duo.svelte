<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apew5yb4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="apew5yb4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:a-duo" {...props}></Icon>
