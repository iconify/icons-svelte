<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0af_p5mt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k0af_p5mt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-headphone-line" {...props}></Icon>
