<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgv4y0x0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="wgv4y0x0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:pump-soap" {...props}></Icon>
