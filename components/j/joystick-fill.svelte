<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_ead3bgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l_ead3bgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:joystick-fill" {...props}></Icon>
