<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/i5vk6db0m.css';
import '../../css/q/qhgxszy5m.css';
import '../../css/l/ljtyofbkq.css';
import '../../css/m/mlhmlnttr.css';
import '../../css/n/nem3swxdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="i5vk6db0m"/><path class="qhgxszy5m wm-k"/><path class="ljtyofbkq wm-a"/><path class="mlhmlnttr wm-k"/><path class="nem3swxdk wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:message-square-text-sketch" {...props}></Icon>
