<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/segasoa9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="segasoa9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:open-panel-filled-right" {...props}></Icon>
