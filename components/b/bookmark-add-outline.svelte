<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3l3hyqzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w3l3hyqzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bookmark-add-outline" {...props}></Icon>
