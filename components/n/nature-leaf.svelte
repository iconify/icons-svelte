<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxpxfkt8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wxpxfkt8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:nature-leaf" {...props}></Icon>
