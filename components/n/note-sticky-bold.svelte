<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e57oocc4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="e57oocc4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:note-sticky-bold" {...props}></Icon>
