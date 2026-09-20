<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vv4shs_gz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vv4shs_gz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fan-2-fill" {...props}></Icon>
