<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_x5wtbpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z_x5wtbpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:donut-line" {...props}></Icon>
