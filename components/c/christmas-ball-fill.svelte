<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/timrc318u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="timrc318u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:christmas-ball-fill" {...props}></Icon>
