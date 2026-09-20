<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlx2f45iv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wlx2f45iv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:digikeyelectronics" {...props}></Icon>
