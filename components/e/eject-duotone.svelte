<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/x43uz2bpw.css';
import '../../css/v/vugflfbio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="x43uz2bpw"/><path class="vugflfbio"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:eject-duotone" {...props}></Icon>
