<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qptdhcbdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qptdhcbdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bulb-2-line" {...props}></Icon>
