<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epd4epbrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="epd4epbrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:anchor-circle-check" {...props}></Icon>
