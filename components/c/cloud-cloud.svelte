<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3zs83btm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y3zs83btm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:cloud-cloud" {...props}></Icon>
