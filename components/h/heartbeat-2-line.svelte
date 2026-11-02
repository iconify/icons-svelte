<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwooc4-dq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zwooc4-dq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:heartbeat-2-line" {...props}></Icon>
