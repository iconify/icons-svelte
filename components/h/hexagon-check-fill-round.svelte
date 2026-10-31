<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cul32lbjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cul32lbjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:hexagon-check-fill-round" {...props}></Icon>
