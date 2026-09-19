<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eh1uod04j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="eh1uod04j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:j-duo" {...props}></Icon>
