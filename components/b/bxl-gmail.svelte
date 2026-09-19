<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8g6cobgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s8g6cobgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-gmail" {...props}></Icon>
