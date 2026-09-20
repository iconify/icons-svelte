<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxdpbebte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hxdpbebte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:keyboard-2-fill" {...props}></Icon>
