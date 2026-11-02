<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dw8koyu9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dw8koyu9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:calendar-arrow-down-fill" {...props}></Icon>
