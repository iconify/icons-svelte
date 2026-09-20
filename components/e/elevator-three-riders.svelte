<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8u7ribjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="z8u7ribjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:elevator-three-riders" {...props}></Icon>
