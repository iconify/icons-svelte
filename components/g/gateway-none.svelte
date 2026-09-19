<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhr271wtu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="nhr271wtu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:gateway-none" {...props}></Icon>
