<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv03ee_gy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hv03ee_gy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:gamepad-check" {...props}></Icon>
