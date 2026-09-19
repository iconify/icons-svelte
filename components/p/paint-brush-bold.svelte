<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgx6o05ak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="zgx6o05ak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:paint-brush-bold" {...props}></Icon>
