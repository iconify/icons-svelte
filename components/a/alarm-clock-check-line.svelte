<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxdsqgbrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yxdsqgbrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:alarm-clock-check-line" {...props}></Icon>
