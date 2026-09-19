<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdvs7m46w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mdvs7m46w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:aperture" {...props}></Icon>
