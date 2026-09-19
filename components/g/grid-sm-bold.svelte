<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytj3mk6kx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ytj3mk6kx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:grid-sm-bold" {...props}></Icon>
