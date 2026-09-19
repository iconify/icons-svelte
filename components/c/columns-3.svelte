<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4f2uacmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="s4f2uacmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:columns-3" {...props}></Icon>
