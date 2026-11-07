<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnb90nbxf.css';
import '../../css/r/rj5bf4blb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnb90nbxf"/><path class="rj5bf4blb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:radar-2-bold-duotone" {...props}></Icon>
