<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/ahro8jb1p.css';
import '../../css/d/d51ngz3_m.css';
import '../../css/k/kfmctjs9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="ahro8jb1p"/><path clip-rule="evenodd" class="d51ngz3_m"/><path clip-rule="evenodd" class="kfmctjs9b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:i-exam-qualification" {...props}></Icon>
