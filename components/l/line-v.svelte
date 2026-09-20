<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqgar4bjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vqgar4bjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:line-v" {...props}></Icon>
