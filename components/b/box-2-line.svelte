<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp3c5t_6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fp3c5t_6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:box-2-line" {...props}></Icon>
