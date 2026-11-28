<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwzz-ps3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwzz-ps3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:calendar-clock-solid" {...props}></Icon>
