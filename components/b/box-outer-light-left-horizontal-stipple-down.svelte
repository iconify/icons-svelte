<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bg-0uvb6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="bg-0uvb6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-outer-light-left-horizontal-stipple-down" {...props}></Icon>
