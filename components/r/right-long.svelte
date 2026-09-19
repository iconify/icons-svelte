<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cts1vkb_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="cts1vkb_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:right-long" {...props}></Icon>
