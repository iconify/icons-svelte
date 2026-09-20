<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcpx__fvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hcpx__fvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:category-filled" {...props}></Icon>
