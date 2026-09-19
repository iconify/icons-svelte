<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1e26ggfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="x1e26ggfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:pencil-outline" {...props}></Icon>
