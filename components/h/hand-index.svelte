<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9j1fpbum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="s9j1fpbum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:hand-index" {...props}></Icon>
