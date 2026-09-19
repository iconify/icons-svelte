<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ce-4x0bzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ce-4x0bzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:q" {...props}></Icon>
