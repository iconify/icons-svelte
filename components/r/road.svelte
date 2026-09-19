<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vp3lfk64n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="vp3lfk64n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:road" {...props}></Icon>
