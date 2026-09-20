<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frq0tfycz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="frq0tfycz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:access-alarms" {...props}></Icon>
