<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5z8pgb7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r5z8pgb7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:horizontal-rule-stroke-16" {...props}></Icon>
