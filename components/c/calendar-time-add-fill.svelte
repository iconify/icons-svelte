<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzu-h2-ey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dzu-h2-ey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:calendar-time-add-fill" {...props}></Icon>
