<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dacda1b4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dacda1b4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-bar-2-fill" {...props}></Icon>
