<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pthb8fbcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pthb8fbcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-youtube" {...props}></Icon>
