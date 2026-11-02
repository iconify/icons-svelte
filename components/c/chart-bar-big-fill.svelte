<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m11i52b0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m11i52b0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-bar-big-fill" {...props}></Icon>
