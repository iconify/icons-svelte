<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0mrpebth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n0mrpebth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:calendar-month-fill" {...props}></Icon>
