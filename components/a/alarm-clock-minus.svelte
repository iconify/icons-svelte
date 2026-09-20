<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myubs7t0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="myubs7t0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:alarm-clock-minus" {...props}></Icon>
