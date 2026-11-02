<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5z2d8bzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u5z2d8bzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:calendar-month-line" {...props}></Icon>
