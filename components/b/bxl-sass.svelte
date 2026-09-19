<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bljlf24ws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bljlf24ws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-sass" {...props}></Icon>
