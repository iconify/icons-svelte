<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3yj_uvhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="r3yj_uvhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:exclamation-circle-bold" {...props}></Icon>
