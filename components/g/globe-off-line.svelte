<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gy7lazj2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gy7lazj2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:globe-off-line" {...props}></Icon>
