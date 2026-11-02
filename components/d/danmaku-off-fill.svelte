<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7wj9tb6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s7wj9tb6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:danmaku-off-fill" {...props}></Icon>
