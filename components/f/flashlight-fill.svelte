<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wk2b9t_sg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wk2b9t_sg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flashlight-fill" {...props}></Icon>
