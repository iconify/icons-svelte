<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukonh3j0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ukonh3j0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-medium-old" {...props}></Icon>
