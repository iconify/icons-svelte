<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ox0dmmllq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ox0dmmllq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-expand-horizontal" {...props}></Icon>
