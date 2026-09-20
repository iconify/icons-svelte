<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvcm6ab0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xvcm6ab0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:award-fill" {...props}></Icon>
