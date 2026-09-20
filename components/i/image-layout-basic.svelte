<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgk9ozbah.css';
import '../../css/k/k79q3xboj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vgk9ozbah"/><circle class="k79q3xboj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:image-layout-basic" {...props}></Icon>
