<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nctb2ac4r.css';
import '../../css/p/pvvdzwnfo.css';
import '../../css/v/vurxrlbvp.css';
import '../../css/p/puhfr9buo.css';
import '../../css/v/vi-anvyiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><g class="nctb2ac4r"><path class="pvvdzwnfo"/><path class="vurxrlbvp"/></g><path clip-rule="evenodd" class="puhfr9buo"/><path clip-rule="evenodd" class="vi-anvyiq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:rewind-print" {...props}></Icon>
