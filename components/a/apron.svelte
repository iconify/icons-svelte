<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oay1xn8pl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="oay1xn8pl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:apron" {...props}></Icon>
