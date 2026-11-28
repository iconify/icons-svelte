<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/can-a6q1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="can-a6q1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:message-square-solid" {...props}></Icon>
