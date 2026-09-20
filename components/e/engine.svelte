<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb31qukaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="tb31qukaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:engine" {...props}></Icon>
