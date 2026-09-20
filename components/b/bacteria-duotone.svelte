<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/ixcurubng.css';
import '../../css/k/ksu2hdvbg.css';
import '../../css/b/b9-b7wbxk.css';
import '../../css/k/kr8qbbc_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ixcurubng"/><path class="ksu2hdvbg"/><path clip-rule="evenodd" class="b9-b7wbxk"/><path class="kr8qbbc_c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bacteria-duotone" {...props}></Icon>
