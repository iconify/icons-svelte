<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lghyv1bbe.css';
import '../../css/a/ao7oa23vf.css';
import '../../css/s/srlliip3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="lghyv1bbe"/><path class="ao7oa23vf"/><path clip-rule="evenodd" class="srlliip3r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:disc" {...props}></Icon>
