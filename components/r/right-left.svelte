<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dl9ffnbqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="dl9ffnbqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:right-left" {...props}></Icon>
