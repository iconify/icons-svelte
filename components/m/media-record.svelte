<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpngveb6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="vpngveb6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:media-record" {...props}></Icon>
