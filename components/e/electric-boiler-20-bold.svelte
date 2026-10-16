<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgbxvebvj.css';
import '../../css/t/tipy9tb0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mgbxvebvj"/><path class="tipy9tb0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electric-boiler-20-bold" {...props}></Icon>
