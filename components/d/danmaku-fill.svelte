<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1f3nzjrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y1f3nzjrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:danmaku-fill" {...props}></Icon>
