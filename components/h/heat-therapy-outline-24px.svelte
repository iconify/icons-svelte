<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jo5fttb-r.css';
import '../../css/a/amotr2b_o.css';
import '../../css/v/vaxyosbrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jo5fttb-r"/><path clip-rule="evenodd" class="amotr2b_o"/><path class="vaxyosbrx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:heat-therapy-outline-24px" {...props}></Icon>
