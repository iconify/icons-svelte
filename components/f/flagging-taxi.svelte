<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfd85mq7p.css';
import '../../css/t/tdi20-bhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pfd85mq7p"/><path class="tdi20-bhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:flagging-taxi" {...props}></Icon>
