<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c93d2obno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c93d2obno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:heater-off" {...props}></Icon>
