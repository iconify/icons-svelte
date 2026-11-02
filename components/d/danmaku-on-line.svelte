<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbclqhbsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lbclqhbsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:danmaku-on-line" {...props}></Icon>
