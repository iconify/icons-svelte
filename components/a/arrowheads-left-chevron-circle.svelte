<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uv29pbcxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="uv29pbcxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:arrowheads-left-chevron-circle" {...props}></Icon>
