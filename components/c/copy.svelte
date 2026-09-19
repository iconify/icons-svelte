<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/l/lgesblbgy.css';
import '../../css/z/zjfjlbc4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lgesblbgy"/><path class="zjfjlbc4b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:copy" {...props}></Icon>
