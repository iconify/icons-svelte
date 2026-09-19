<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8dx_rb0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="e8dx_rb0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:canoe-outline" {...props}></Icon>
