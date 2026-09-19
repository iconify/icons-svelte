<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vl_3njf8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="vl_3njf8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:four-outline" {...props}></Icon>
