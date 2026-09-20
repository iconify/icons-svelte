<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dg16p0b8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dg16p0b8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:bed" {...props}></Icon>
