<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_8xx_b4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l_8xx_b4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:maps-arrow-xmark" {...props}></Icon>
