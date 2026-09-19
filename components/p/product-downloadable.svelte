<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wldpzndwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wldpzndwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:product-downloadable" {...props}></Icon>
