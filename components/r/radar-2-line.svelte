<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdx_jfjiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wdx_jfjiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:radar-2-line" {...props}></Icon>
