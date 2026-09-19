<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/et9yusbvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="et9yusbvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:brightness" {...props}></Icon>
