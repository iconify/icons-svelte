<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvk_8sbkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dvk_8sbkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bicycle-and-dollar" {...props}></Icon>
