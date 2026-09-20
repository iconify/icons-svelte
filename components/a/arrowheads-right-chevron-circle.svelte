<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yh3jj2bim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yh3jj2bim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:arrowheads-right-chevron-circle" {...props}></Icon>
