<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7-8-1t_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="l7-8-1t_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pixel-circle-with-dot" {...props}></Icon>
