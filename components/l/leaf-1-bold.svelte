<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dh5frxbwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="dh5frxbwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:leaf-1-bold" {...props}></Icon>
