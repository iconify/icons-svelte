<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghp_0ac9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ghp_0ac9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:i-duo" {...props}></Icon>
