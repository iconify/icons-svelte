<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fyzm3zbky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="fyzm3zbky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:record-bold" {...props}></Icon>
