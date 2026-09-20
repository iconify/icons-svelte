<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_udngbdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="w_udngbdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:dharma-wheel-on-square" {...props}></Icon>
