<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f221h1bhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="f221h1bhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:circle-info" {...props}></Icon>
