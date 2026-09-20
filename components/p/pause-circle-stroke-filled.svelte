<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gy42w6b_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gy42w6b_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:pause-circle-stroke-filled" {...props}></Icon>
