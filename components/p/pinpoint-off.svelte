<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/c17l0cbmj.css';
import '../../css/j/jmpl9nzbh.css';
import '../../css/n/n_-73ibvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="c17l0cbmj"/><path clip-rule="evenodd" class="jmpl9nzbh"/><path clip-rule="evenodd" class="n_-73ibvy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:pinpoint-off" {...props}></Icon>
