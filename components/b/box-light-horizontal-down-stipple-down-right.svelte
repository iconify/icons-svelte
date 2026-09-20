<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7ou676du.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="s7ou676du"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-horizontal-down-stipple-down-right" {...props}></Icon>
