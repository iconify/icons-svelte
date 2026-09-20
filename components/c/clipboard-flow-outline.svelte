<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbf406y8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lbf406y8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clipboard-flow-outline" {...props}></Icon>
