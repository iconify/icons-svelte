<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/by1cai91s.css';
import '../../css/h/htry6xr6b.css';
import '../../css/u/ut-gx-b7l.css';
import '../../css/x/xtpeb-edw.css';
import '../../css/c/ctjqh1aad.css';
import '../../css/s/shjp9pbqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="by1cai91s"/><path class="htry6xr6b"/><path class="ut-gx-b7l"/><g class="xtpeb-edw"><path class="ctjqh1aad"/><path class="shjp9pbqe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:planet-4-bold-duotone" {...props}></Icon>
