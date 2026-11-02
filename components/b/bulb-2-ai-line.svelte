<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cd_m56bka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cd_m56bka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bulb-2-ai-line" {...props}></Icon>
