<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9pw1tb7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="p9pw1tb7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:elevator-bold" {...props}></Icon>
