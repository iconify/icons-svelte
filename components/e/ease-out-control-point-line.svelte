<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqtso2iev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vqtso2iev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ease-out-control-point-line" {...props}></Icon>
