<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxdl1iumf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxdl1iumf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:invoice-outline" {...props}></Icon>
