<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccj1-zbif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ccj1-zbif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:pie-chart-box-line" {...props}></Icon>
