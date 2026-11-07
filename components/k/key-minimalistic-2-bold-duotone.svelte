<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhw3f2lhi.css';
import '../../css/h/halx4mbsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uhw3f2lhi"/><path class="halx4mbsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:key-minimalistic-2-bold-duotone" {...props}></Icon>
