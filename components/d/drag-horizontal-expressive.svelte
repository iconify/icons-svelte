<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cp93dz86h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cp93dz86h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:drag-horizontal-expressive" {...props}></Icon>
