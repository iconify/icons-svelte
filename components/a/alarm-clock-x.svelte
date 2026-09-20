<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcq7k6bmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vcq7k6bmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:alarm-clock-x" {...props}></Icon>
