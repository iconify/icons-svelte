<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvx3s30_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dvx3s30_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:grip-horizontal-line" {...props}></Icon>
