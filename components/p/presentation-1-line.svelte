<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqiq-ebfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hqiq-ebfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:presentation-1-line" {...props}></Icon>
