<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u50rtftbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u50rtftbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:joystick-filled" {...props}></Icon>
