<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ha5r7tnjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ha5r7tnjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:check-circle-line" {...props}></Icon>
