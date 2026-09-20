<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ethff8bix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ethff8bix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:media-network" {...props}></Icon>
