<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke6bw-_7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="ke6bw-_7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:arrow-thin-left-top" {...props}></Icon>
