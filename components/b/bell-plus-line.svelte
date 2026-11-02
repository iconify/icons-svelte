<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yn145___z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yn145___z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bell-plus-line" {...props}></Icon>
