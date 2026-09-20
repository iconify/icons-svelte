<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_67od41a.css';
import '../../css/j/jhuhxq2cd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q_67od41a"/><path class="jhuhxq2cd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:microphone" {...props}></Icon>
