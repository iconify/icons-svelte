<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvx1azbsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pvx1azbsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:bell-gear" {...props}></Icon>
