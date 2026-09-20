<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyp6jzb_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gyp6jzb_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:pie-chart-2-fill" {...props}></Icon>
