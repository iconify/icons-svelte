<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e26w32bwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e26w32bwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bluetooth" {...props}></Icon>
