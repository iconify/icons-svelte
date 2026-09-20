<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gg71r1byf.css';
import '../../css/a/ajf_7ldit.css';
import '../../css/n/npr0pslmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gg71r1byf"/><path class="ajf_7ldit"/><path clip-rule="evenodd" class="npr0pslmk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:pen-nib2-filled" {...props}></Icon>
