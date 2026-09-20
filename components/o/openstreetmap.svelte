<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-vkvrb4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z-vkvrb4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:openstreetmap" {...props}></Icon>
