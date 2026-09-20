<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cc-jrob2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cc-jrob2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:align-horizontal-distribute-start" {...props}></Icon>
