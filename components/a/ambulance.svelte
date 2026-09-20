<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g03q9xe2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g03q9xe2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:ambulance" {...props}></Icon>
