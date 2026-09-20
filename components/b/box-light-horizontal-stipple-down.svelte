<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_ouxubdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="b_ouxubdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-horizontal-stipple-down" {...props}></Icon>
