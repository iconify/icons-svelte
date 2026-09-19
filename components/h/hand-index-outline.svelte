<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3x2en2ew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="b3x2en2ew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:hand-index-outline" {...props}></Icon>
