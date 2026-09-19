<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f69k5ob-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="f69k5ob-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:movie-projector" {...props}></Icon>
