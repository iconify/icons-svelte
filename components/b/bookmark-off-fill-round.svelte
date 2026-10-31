<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vsh8bwo5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vsh8bwo5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bookmark-off-fill-round" {...props}></Icon>
