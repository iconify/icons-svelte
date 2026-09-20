<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7qs3tb9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="c7qs3tb9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arrow-down-to-wide-rectangle-outline" {...props}></Icon>
