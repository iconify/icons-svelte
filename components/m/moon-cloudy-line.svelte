<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/el-0wrg4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="el-0wrg4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:moon-cloudy-line" {...props}></Icon>
