<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rm_q50s4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rm_q50s4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-u-down-left-bold" {...props}></Icon>
