<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yom7c30uv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="yom7c30uv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:chevron-circle-bold" {...props}></Icon>
