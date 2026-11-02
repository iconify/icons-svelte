<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0cr4vzca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n0cr4vzca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:calendar-3-line" {...props}></Icon>
