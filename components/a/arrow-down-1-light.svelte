<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sglkbcbsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sglkbcbsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-down-1-light" {...props}></Icon>
