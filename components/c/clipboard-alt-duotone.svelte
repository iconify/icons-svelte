<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/z39rhmxzt.css';
import '../../css/g/gsepfxz2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="z39rhmxzt"/><path class="gsepfxz2y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:clipboard-alt-duotone" {...props}></Icon>
