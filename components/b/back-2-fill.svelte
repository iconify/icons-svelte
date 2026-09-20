<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mk3mi57fy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mk3mi57fy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:back-2-fill" {...props}></Icon>
