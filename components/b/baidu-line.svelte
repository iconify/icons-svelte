<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfrp_vl4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lfrp_vl4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:baidu-line" {...props}></Icon>
