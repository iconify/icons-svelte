<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0ukv68fm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t0ukv68fm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cellphone-charging" {...props}></Icon>
