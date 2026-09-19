<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wv1ssxzig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="wv1ssxzig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:fullscreen" {...props}></Icon>
