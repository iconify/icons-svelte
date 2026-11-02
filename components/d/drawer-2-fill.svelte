<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mq_j_249x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mq_j_249x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:drawer-2-fill" {...props}></Icon>
