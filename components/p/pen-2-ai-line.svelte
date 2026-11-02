<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5vryobju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y5vryobju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pen-2-ai-line" {...props}></Icon>
