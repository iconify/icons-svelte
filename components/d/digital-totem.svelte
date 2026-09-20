<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv-n-8s8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nv-n-8s8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:digital-totem" {...props}></Icon>
