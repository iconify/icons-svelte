<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zf6jplrjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="zf6jplrjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bezier-diamond-outline" {...props}></Icon>
