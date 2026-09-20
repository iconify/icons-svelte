<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdu5r8brx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jdu5r8brx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-vision-pro-filled" {...props}></Icon>
