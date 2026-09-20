<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cc-xlvwvo.css';
import '../../css/q/qsgxnsjgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cc-xlvwvo"/><path class="qsgxnsjgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:moonlight-line" {...props}></Icon>
