<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qc3w0nb0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qc3w0nb0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:message-circle-x" {...props}></Icon>
