<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uclud-n7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uclud-n7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-rupee-line" {...props}></Icon>
