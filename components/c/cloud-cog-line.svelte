<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbd_63bfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mbd_63bfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cloud-cog-line" {...props}></Icon>
