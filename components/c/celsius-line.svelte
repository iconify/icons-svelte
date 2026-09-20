<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n29yr30op.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n29yr30op"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:celsius-line" {...props}></Icon>
