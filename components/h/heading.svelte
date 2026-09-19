<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ab7bv8b0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ab7bv8b0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:heading" {...props}></Icon>
