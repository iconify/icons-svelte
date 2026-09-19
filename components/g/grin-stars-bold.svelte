<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrl0tvb8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="xrl0tvb8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:grin-stars-bold" {...props}></Icon>
