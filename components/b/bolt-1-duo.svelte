<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2357wbmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="s2357wbmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bolt-1-duo" {...props}></Icon>
