<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzdlp6bkl.css';
import '../../css/s/sxsjrzbyv.css';
import '../../css/l/lj70h7b9m.css';
import '../../css/o/ozbpad-uv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="zzdlp6bkl"/><g class="sxsjrzbyv"><path class="lj70h7b9m"/><path class="ozbpad-uv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:eject-button" {...props}></Icon>
