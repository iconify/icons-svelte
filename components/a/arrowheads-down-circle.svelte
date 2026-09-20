<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4qh7ybap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="h4qh7ybap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:arrowheads-down-circle" {...props}></Icon>
