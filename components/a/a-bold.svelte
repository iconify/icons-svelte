<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwemtzb2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="xwemtzb2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:a-bold" {...props}></Icon>
