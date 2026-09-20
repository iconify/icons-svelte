<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ug_j8ebhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ug_j8ebhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:north" {...props}></Icon>
