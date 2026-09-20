<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tk9z7dtrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tk9z7dtrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:emoji-robot-angry" {...props}></Icon>
