<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfk5-2ass.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kfk5-2ass"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:danmaku-line" {...props}></Icon>
