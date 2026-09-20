<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ceqw9tbxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ceqw9tbxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:cube" {...props}></Icon>
