<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fy6kykofr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fy6kykofr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:medical-instrument-walking-aid-bold" {...props}></Icon>
