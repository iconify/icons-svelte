<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xt8s8dbkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xt8s8dbkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:duck-in-water" {...props}></Icon>
