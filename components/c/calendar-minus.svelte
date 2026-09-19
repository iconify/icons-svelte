<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yn_3ohb_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="yn_3ohb_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:calendar-minus" {...props}></Icon>
