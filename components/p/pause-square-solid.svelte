<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulaa0sbdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ulaa0sbdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:pause-square-solid" {...props}></Icon>
