<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0ipujbft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="s0ipujbft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:map-rm" {...props}></Icon>
