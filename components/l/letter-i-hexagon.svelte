<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcemut8oi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rcemut8oi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-i-hexagon" {...props}></Icon>
