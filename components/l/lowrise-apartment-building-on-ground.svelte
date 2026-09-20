<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-kg16b2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="x-kg16b2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:lowrise-apartment-building-on-ground" {...props}></Icon>
