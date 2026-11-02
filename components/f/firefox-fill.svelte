<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-yhy6bof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h-yhy6bof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:firefox-fill" {...props}></Icon>
