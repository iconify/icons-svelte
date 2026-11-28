<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtdojlb_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rtdojlb_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:parachute-solid" {...props}></Icon>
