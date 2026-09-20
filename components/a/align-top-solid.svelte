<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln15bwbav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ln15bwbav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:align-top-solid" {...props}></Icon>
