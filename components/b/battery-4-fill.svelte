<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzp36sxgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jzp36sxgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:battery-4-fill" {...props}></Icon>
