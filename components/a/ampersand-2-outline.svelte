<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxj1znb5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="pxj1znb5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:ampersand-2-outline" {...props}></Icon>
