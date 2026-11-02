<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycf1h_bmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ycf1h_bmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:list-start-line" {...props}></Icon>
