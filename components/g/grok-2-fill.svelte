<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yn8g1ddly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yn8g1ddly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:grok-2-fill" {...props}></Icon>
