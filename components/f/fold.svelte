<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obgjjz6ai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="obgjjz6ai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:fold" {...props}></Icon>
