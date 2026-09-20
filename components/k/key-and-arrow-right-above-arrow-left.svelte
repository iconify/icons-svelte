<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdo_mb58d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zdo_mb58d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:key-and-arrow-right-above-arrow-left" {...props}></Icon>
