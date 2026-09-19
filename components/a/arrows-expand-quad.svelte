<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2u5f7bvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="s2u5f7bvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:arrows-expand-quad" {...props}></Icon>
