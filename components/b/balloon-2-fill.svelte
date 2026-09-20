<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsa_hubve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xsa_hubve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:balloon-2-fill" {...props}></Icon>
