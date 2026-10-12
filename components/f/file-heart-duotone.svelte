<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f6u69tk9d.css';
import '../../css/y/y8ppixbeg.css';
import '../../css/o/omi4i4cer.css';
import '../../css/w/wy30a9trv.css';
import '../../css/a/ab-i7abzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f6u69tk9d"/><path class="y8ppixbeg"/><path class="omi4i4cer"/><path class="wy30a9trv"/><path class="ab-i7abzq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:file-heart-duotone" {...props}></Icon>
