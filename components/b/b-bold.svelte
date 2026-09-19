<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yazykqgsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="yazykqgsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:b-bold" {...props}></Icon>
