<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibf5nlbkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ibf5nlbkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:human-head" {...props}></Icon>
