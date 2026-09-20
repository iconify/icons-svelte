<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftd8t6bpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ftd8t6bpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:linejoin-bevel-outline" {...props}></Icon>
