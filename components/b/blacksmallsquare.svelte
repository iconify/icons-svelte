<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pypo4hbot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pypo4hbot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:blacksmallsquare" {...props}></Icon>
