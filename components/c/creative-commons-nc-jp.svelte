<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yt3rp2b8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yt3rp2b8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:creative-commons-nc-jp" {...props}></Icon>
