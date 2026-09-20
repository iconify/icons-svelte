<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfc2vbcbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sfc2vbcbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:camcorder" {...props}></Icon>
