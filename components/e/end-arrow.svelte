<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smpgmkb8n.css';
import '../../css/i/iush4bsal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="smpgmkb8n"/><path class="iush4bsal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:end-arrow" {...props}></Icon>
