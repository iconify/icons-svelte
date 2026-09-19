<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fparxj4eo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="fparxj4eo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:d-pad-1-bold" {...props}></Icon>
