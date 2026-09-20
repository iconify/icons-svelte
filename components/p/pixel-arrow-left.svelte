<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m50n4vfob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m50n4vfob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pixel-arrow-left" {...props}></Icon>
