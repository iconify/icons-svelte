<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ju9d-d0dv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ju9d-d0dv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-bing" {...props}></Icon>
