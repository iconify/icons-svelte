<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m68fv6b_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m68fv6b_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:hand-dropping-circles" {...props}></Icon>
