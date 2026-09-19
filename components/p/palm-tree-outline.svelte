<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5eihabei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="c5eihabei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:palm-tree-outline" {...props}></Icon>
