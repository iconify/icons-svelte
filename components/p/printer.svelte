<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/si_h8nlvt.css';
import '../../css/i/i817x4i-m.css';
import '../../css/b/bt2vhjbuk.css';
import '../../css/e/e6sihfv7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="si_h8nlvt"/><path class="i817x4i-m"/><path class="bt2vhjbuk"/><path class="e6sihfv7n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:printer" {...props}></Icon>
