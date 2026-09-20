<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae_0a0bxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ae_0a0bxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:arrowheads-right" {...props}></Icon>
