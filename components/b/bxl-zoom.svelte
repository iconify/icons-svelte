<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rk31ljb9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rk31ljb9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-zoom" {...props}></Icon>
