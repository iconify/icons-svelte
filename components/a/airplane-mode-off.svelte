<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmj35zbax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bmj35zbax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:airplane-mode-off" {...props}></Icon>
