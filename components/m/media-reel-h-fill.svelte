<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1-3iubmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d1-3iubmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:media-reel-h-fill" {...props}></Icon>
