<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qp1-osbvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qp1-osbvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cloud-snow-line" {...props}></Icon>
