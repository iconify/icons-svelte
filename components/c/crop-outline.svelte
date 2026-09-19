<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyllv6izc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="eyllv6izc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:crop-outline" {...props}></Icon>
