<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzmxtt7ys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uzmxtt7ys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:calendar-day-fill" {...props}></Icon>
