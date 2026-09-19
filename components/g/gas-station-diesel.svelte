<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgjiwmb0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vgjiwmb0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:gas-station-diesel" {...props}></Icon>
