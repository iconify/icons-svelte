<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zweq5cbwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="zweq5cbwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:note-pad-1-bold" {...props}></Icon>
