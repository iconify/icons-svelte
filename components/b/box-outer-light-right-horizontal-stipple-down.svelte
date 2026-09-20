<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8-xambrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="q8-xambrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-outer-light-right-horizontal-stipple-down" {...props}></Icon>
