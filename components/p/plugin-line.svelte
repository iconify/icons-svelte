<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmsd93b9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bmsd93b9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:plugin-line" {...props}></Icon>
