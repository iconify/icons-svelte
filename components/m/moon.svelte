<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0mv-cb_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="w0mv-cb_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:moon" {...props}></Icon>
