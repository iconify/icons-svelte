<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ysyqcrbhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ysyqcrbhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:mood-tongue-outline" {...props}></Icon>
