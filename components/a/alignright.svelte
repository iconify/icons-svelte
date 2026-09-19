<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ey-ar0bsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":666,"height":644};
const content = `<path class="ey-ar0bsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:alignright" {...props}></Icon>
