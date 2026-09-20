<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wd8e2usik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wd8e2usik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:motorboat-and-arrow-right-above-arrow-left" {...props}></Icon>
