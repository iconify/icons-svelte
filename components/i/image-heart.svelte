<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p33r84bbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p33r84bbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:image-heart" {...props}></Icon>
