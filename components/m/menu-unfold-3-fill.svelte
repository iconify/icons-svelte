<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhpyfvb_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xhpyfvb_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:menu-unfold-3-fill" {...props}></Icon>
