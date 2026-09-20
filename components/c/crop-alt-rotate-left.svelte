<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fn6_se3_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fn6_se3_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:crop-alt-rotate-left" {...props}></Icon>
