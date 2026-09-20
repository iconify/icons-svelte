<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tk6_03hfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tk6_03hfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:place-of-worship-building" {...props}></Icon>
