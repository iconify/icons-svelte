<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrld43bwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zrld43bwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:bell" {...props}></Icon>
