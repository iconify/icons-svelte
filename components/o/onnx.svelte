<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xazcw1buf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xazcw1buf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:onnx" {...props}></Icon>
