<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zps83bc6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zps83bc6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:emoji-kiss" {...props}></Icon>
