<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yuo_w0z7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yuo_w0z7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:flower3" {...props}></Icon>
