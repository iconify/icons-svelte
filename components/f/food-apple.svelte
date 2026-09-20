<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3vo60byr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r3vo60byr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:food-apple" {...props}></Icon>
