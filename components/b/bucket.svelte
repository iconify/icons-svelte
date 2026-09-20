<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s02vp9brs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="s02vp9brs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bucket" {...props}></Icon>
