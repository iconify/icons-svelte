<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7zw--b-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="u7zw--b-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:note-clipboard-bold" {...props}></Icon>
