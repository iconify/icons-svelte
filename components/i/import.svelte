<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d15z4kwjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d15z4kwjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:import" {...props}></Icon>
