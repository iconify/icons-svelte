<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvr8x-hfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dvr8x-hfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:distribute-horizontal-round" {...props}></Icon>
