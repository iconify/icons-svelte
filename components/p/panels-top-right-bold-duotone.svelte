<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2c2_w_6w.css';
import '../../css/r/r59yt9kbk.css';
import '../../css/i/ihrvnl4wp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y2c2_w_6w"/><path class="r59yt9kbk"/><path class="ihrvnl4wp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panels-top-right-bold-duotone" {...props}></Icon>
