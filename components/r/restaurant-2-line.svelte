<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/up0j-lbhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="up0j-lbhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:restaurant-2-line" {...props}></Icon>
