<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhq3foupt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xhq3foupt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-flag-alt" {...props}></Icon>
