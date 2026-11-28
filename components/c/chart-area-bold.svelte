<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psqsc1boi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="psqsc1boi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:chart-area-bold" {...props}></Icon>
