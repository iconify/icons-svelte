<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6p0izbuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g6p0izbuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:building-4-fill-round" {...props}></Icon>
