<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rem292bvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="rem292bvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-outer-light-up-vertical-stipple-left" {...props}></Icon>
