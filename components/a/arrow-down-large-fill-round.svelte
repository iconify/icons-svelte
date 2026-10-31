<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qx-73pble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qx-73pble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-down-large-fill-round" {...props}></Icon>
