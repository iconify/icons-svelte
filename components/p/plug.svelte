<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-vp-bb3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="g-vp-bb3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:plug" {...props}></Icon>
