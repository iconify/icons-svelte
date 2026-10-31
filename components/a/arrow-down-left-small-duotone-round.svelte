<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8buvebpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l8buvebpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-down-left-small-duotone-round" {...props}></Icon>
