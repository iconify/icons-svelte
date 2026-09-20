<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rs5dpr2nu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="rs5dpr2nu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:funnel" {...props}></Icon>
