<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cewd985tv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cewd985tv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:power-tower-delta" {...props}></Icon>
