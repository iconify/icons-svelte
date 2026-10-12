<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/g9nxijbxs.css';
import '../../css/y/y8ppixbeg.css';
import '../../css/o/omi4i4cer.css';
import '../../css/c/cr2hv5bad.css';
import '../../css/v/vjgf328hd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="g9nxijbxs"/><path class="y8ppixbeg"/><path class="omi4i4cer"/><path class="cr2hv5bad"/><path class="vjgf328hd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:file-volume-duotone" {...props}></Icon>
