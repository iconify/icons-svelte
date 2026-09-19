<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fm9kbmb7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="fm9kbmb7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:hand-index-bold" {...props}></Icon>
