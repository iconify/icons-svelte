<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/ps73y_alv.css';
import '../../css/a/a5neubxnb.css';
import '../../css/n/n4ra6qb5a.css';
import '../../css/h/h4uzyibtm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ps73y_alv"/><path class="a5neubxnb wm-s"/><path class="n4ra6qb5a"/><path class="h4uzyibtm wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:flashlight-duo" {...props}></Icon>
