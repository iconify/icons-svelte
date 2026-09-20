<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahhxt3bgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ahhxt3bgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:arrowheads-left-chevron" {...props}></Icon>
