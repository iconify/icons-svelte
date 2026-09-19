<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8-47p4hb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l8-47p4hb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:circuit-board-filled" {...props}></Icon>
