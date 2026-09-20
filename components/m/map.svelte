<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyu3vjbhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lyu3vjbhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:map" {...props}></Icon>
