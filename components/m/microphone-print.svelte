<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bfziqobfb.css';
import '../../css/c/cbxxtsb9k.css';
import '../../css/t/ti51-gb4g.css';
import '../../css/e/ecwe_bfgh.css';
import '../../css/j/jsunwxbwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="bfziqobfb"/><path clip-rule="evenodd" class="cbxxtsb9k"/><path class="ti51-gb4g"/><path class="ecwe_bfgh"/><path class="jsunwxbwb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:microphone-print" {...props}></Icon>
