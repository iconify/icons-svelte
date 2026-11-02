<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8-cp0bpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u8-cp0bpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:indent-increase-fill" {...props}></Icon>
