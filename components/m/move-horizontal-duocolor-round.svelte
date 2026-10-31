<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1-uwksly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u1-uwksly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:move-horizontal-duocolor-round" {...props}></Icon>
