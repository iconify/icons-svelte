<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofe-j50dh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="ofe-j50dh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:circle-triangle-right" {...props}></Icon>
