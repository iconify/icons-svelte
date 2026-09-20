<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-7jbtbrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-7jbtbrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:infrared-thermometer-line" {...props}></Icon>
