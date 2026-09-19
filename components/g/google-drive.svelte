<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2i3shp5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="w2i3shp5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:google-drive" {...props}></Icon>
