<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnidoqb7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnidoqb7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:gemini-line" {...props}></Icon>
