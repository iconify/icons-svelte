<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vf0ka5mro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="vf0ka5mro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:forward" {...props}></Icon>
