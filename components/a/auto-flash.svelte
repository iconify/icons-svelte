<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lm1lufbty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="lm1lufbty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:auto-flash" {...props}></Icon>
