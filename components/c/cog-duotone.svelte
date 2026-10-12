<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/b-dwepbcd.css';
import '../../css/r/rrk1nfbye.css';
import '../../css/v/v2hkzdbqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="b-dwepbcd"/><path class="rrk1nfbye"/><path clip-rule="evenodd" class="v2hkzdbqr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cog-duotone" {...props}></Icon>
