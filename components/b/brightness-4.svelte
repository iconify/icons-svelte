<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipw1llb-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ipw1llb-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:brightness-4" {...props}></Icon>
