<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xw-_-kbhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xw-_-kbhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:microchip" {...props}></Icon>
