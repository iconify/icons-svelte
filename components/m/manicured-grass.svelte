<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbn5igc_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nbn5igc_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:manicured-grass" {...props}></Icon>
