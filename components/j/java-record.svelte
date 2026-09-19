<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j36ff-b8d.css';
import '../../css/q/qeixe-bjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j36ff-b8d"/><path class="qeixe-bjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:java-record" {...props}></Icon>
