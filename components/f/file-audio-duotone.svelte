<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lhj0lixiu.css';
import '../../css/t/ti90qacav.css';
import '../../css/z/z7bc25blt.css';
import '../../css/j/jvx3o2lpn.css';
import '../../css/q/qeyj3-b5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lhj0lixiu"/><path class="ti90qacav"/><path class="z7bc25blt"/><circle class="jvx3o2lpn"/><path class="qeyj3-b5i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:file-audio-duotone" {...props}></Icon>
