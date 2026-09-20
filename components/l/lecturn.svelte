<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t80ry2bfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t80ry2bfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:lecturn" {...props}></Icon>
