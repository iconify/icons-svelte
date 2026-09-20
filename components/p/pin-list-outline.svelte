<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/w222tbclf.css';
import '../../css/b/bg2z60l4k.css';
import '../../css/f/fcsgee45r.css';
import '../../css/d/drb7xldnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="w222tbclf"/><path class="bg2z60l4k"/><path class="fcsgee45r"/><path class="drb7xldnm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pin-list-outline" {...props}></Icon>
