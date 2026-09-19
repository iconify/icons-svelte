<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idga7wb7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="idga7wb7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:gas-station-eco" {...props}></Icon>
