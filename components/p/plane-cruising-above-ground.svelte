<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhg3wg2ot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nhg3wg2ot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:plane-cruising-above-ground" {...props}></Icon>
