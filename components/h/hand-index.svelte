<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cysgz9bwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="cysgz9bwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:hand-index" {...props}></Icon>
