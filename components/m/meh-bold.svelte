<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sp5lgw7sw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="sp5lgw7sw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:meh-bold" {...props}></Icon>
