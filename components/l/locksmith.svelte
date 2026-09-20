<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcwv75bft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="fcwv75bft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:locksmith" {...props}></Icon>
