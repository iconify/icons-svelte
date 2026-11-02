<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lasmuzh_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lasmuzh_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:camcorder-3-line" {...props}></Icon>
