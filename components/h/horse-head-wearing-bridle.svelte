<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/se0wmr1vr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="se0wmr1vr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:horse-head-wearing-bridle" {...props}></Icon>
