<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-xz9t4wa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="u-xz9t4wa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:arrowheads-down-left-chevron-circle" {...props}></Icon>
