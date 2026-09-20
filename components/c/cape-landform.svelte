<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8f6orbuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="l8f6orbuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:cape-landform" {...props}></Icon>
