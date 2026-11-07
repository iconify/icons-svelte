<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szsyyvgyx.css';
import '../../css/e/e_dihi53c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="szsyyvgyx"/><path class="e_dihi53c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:notes-minimalistic-bold" {...props}></Icon>
