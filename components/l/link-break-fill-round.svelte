<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/heb04wnhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="heb04wnhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:link-break-fill-round" {...props}></Icon>
