<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uq7yxmbdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uq7yxmbdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:party-popper-star" {...props}></Icon>
