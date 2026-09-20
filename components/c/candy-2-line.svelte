<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iy61_00yi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iy61_00yi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:candy-2-line" {...props}></Icon>
