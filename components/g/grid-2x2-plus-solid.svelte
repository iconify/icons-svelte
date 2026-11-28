<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ox8_lzbbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ox8_lzbbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:grid-2x2-plus-solid" {...props}></Icon>
