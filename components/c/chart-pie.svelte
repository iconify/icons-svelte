<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whk9toiwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="whk9toiwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:chart-pie" {...props}></Icon>
