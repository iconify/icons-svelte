<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srat1eb3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="srat1eb3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:lips-duo" {...props}></Icon>
