<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfy61bqzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sfy61bqzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:danmaku-fill" {...props}></Icon>
