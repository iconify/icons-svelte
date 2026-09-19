<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvpz3_mij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="bvpz3_mij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:hand-call" {...props}></Icon>
