<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo4-bjbdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xo4-bjbdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:charles-schwab-light" {...props}></Icon>
