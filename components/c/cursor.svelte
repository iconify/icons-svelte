<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9jb0-bzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="h9jb0-bzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:cursor" {...props}></Icon>
