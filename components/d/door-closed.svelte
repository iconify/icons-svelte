<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p67ppjbjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p67ppjbjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:door-closed" {...props}></Icon>
