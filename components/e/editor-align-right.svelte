<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rv1o7x2xo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rv1o7x2xo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:editor-align-right" {...props}></Icon>
