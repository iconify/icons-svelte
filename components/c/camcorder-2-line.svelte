<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9bn8ob3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m9bn8ob3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:camcorder-2-line" {...props}></Icon>
