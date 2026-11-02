<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5a2eljqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e5a2eljqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:calendar-time-add-fill" {...props}></Icon>
