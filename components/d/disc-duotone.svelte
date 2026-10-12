<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/g4vvtk_cw.css';
import '../../css/n/nzmariesu.css';
import '../../css/v/v5f2xdb6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="g4vvtk_cw"/><path class="nzmariesu"/><path clip-rule="evenodd" class="v5f2xdb6t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:disc-duotone" {...props}></Icon>
