<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/f/fv3a1acik.css';
import '../../css/m/m6a3e3btz.css';
import '../../css/p/p0sd-vr-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fv3a1acik"/><rect class="m6a3e3btz"/><path class="p0sd-vr-x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:hard-drive-upload" {...props}></Icon>
