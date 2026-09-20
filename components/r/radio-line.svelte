<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ryh7p5bve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ryh7p5bve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:radio-line" {...props}></Icon>
