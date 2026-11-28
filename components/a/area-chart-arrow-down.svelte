<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbizf5inb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cbizf5inb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:area-chart-arrow-down" {...props}></Icon>
