<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6hv0acym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w6hv0acym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-right-down-line" {...props}></Icon>
