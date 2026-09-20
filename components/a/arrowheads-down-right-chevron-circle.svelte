<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3uraec-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="y3uraec-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:arrowheads-down-right-chevron-circle" {...props}></Icon>
