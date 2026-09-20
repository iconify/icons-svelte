<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ed_o99bvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ed_o99bvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:cloud-search" {...props}></Icon>
