<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tj3lf2btc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":17};
const content = `<path class="tj3lf2btc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:art-board" {...props}></Icon>
