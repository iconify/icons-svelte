<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsa0oe37a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zsa0oe37a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:printer-point-of-sale-play-outline" {...props}></Icon>
