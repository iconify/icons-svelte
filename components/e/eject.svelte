<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yglz00bkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="yglz00bkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:eject" {...props}></Icon>
