<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9_cg6g2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="u9_cg6g2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:arrowheads-down-right" {...props}></Icon>
