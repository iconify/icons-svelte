<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_0irbrkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g_0irbrkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-down-circle-fill" {...props}></Icon>
