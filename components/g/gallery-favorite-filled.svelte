<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/b8hfadckz.css';
import '../../css/a/a05xr_gmb.css';
import '../../css/g/ggxoisrbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="b8hfadckz"/><path class="a05xr_gmb"/><path class="ggxoisrbh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:gallery-favorite-filled" {...props}></Icon>
