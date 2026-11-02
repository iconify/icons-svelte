<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zehq18b8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zehq18b8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-big-down-dash-fill" {...props}></Icon>
