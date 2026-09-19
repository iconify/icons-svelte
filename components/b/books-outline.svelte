<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cg0zrubmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="cg0zrubmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:books-outline" {...props}></Icon>
