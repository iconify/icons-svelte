<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vod-ixb0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="vod-ixb0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:h-2-outline" {...props}></Icon>
