<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqhs-rbdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cqhs-rbdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:eraser-ai-line" {...props}></Icon>
