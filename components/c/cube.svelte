<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m16dw2hxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m16dw2hxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:cube" {...props}></Icon>
