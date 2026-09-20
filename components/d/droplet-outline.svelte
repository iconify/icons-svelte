<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6j_wib5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="y6j_wib5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:droplet-outline" {...props}></Icon>
