<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmgnkr10o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="jmgnkr10o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:pin-location-add" {...props}></Icon>
