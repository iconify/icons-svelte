<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dn9c1cdua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="dn9c1cdua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:arrowheads-down-right-chevron" {...props}></Icon>
