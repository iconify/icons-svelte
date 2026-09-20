<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewb1r_bgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ewb1r_bgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-laptop-off" {...props}></Icon>
