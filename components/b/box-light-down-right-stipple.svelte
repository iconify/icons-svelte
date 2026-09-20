<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5ewptvhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="y5ewptvhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-down-right-stipple" {...props}></Icon>
