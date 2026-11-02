<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zk-q_ac3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zk-q_ac3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:greatwall-line" {...props}></Icon>
