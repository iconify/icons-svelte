<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tuhnk4qnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="tuhnk4qnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-vertical-horizontal-stipple-right-down-left" {...props}></Icon>
