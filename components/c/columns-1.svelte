<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxifazq2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="rxifazq2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:columns-1" {...props}></Icon>
