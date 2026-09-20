<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6s6g16ad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n6s6g16ad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:image-layout-frameless" {...props}></Icon>
