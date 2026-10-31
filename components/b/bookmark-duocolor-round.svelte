<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iiajows2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iiajows2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bookmark-duocolor-round" {...props}></Icon>
