<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wz2q7telr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wz2q7telr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:corner-right-down-fill" {...props}></Icon>
