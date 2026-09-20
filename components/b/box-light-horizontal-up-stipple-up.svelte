<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dad9_nbwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="dad9_nbwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-horizontal-up-stipple-up" {...props}></Icon>
