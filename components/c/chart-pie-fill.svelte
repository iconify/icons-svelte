<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sb0ybnbxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sb0ybnbxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-pie-fill" {...props}></Icon>
