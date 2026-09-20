<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gw_fnybwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gw_fnybwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:calendar-times-solid" {...props}></Icon>
