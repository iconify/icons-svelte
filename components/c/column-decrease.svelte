<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qt5219fsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="qt5219fsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:column-decrease" {...props}></Icon>
