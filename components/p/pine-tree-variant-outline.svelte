<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdw90cclc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wdw90cclc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pine-tree-variant-outline" {...props}></Icon>
