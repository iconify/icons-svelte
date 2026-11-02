<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rs5be5bek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rs5be5bek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mic-ai-line" {...props}></Icon>
