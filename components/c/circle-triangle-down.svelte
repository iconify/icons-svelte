<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctuk4ds0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="ctuk4ds0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:circle-triangle-down" {...props}></Icon>
