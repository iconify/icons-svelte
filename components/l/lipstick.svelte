<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y79b0gbxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y79b0gbxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:lipstick" {...props}></Icon>
