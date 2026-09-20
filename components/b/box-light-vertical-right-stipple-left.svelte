<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bv2lx-mpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="bv2lx-mpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-vertical-right-stipple-left" {...props}></Icon>
