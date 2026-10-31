<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-4o8eb7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-4o8eb7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:joystick-round" {...props}></Icon>
