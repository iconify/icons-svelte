<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qovv2hjaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qovv2hjaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:picture-in-picture-top-right" {...props}></Icon>
