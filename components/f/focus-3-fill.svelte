<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgqeagbus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mgqeagbus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:focus-3-fill" {...props}></Icon>
