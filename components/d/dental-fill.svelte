<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m64y0ybiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m64y0ybiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dental-fill" {...props}></Icon>
