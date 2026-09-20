<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvyztpgpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="yvyztpgpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-outer-light-down-stipple" {...props}></Icon>
