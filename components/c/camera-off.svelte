<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwjuxs-hx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uwjuxs-hx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:camera-off" {...props}></Icon>
