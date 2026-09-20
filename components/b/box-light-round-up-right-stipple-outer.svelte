<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrs40vbfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="vrs40vbfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-round-up-right-stipple-outer" {...props}></Icon>
