<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq14dwolm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qq14dwolm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-wearing-racing-helmet-driving-racecar" {...props}></Icon>
