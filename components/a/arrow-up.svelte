<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tolvt1byo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="tolvt1byo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:arrow-up" {...props}></Icon>
