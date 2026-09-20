<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ki4-hdcdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ki4-hdcdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:large-arrow-left-line" {...props}></Icon>
