<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wh_a1ub3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wh_a1ub3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:axe-and-chipped-log" {...props}></Icon>
