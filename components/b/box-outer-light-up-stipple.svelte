<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cp5o4dbvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="cp5o4dbvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-outer-light-up-stipple" {...props}></Icon>
