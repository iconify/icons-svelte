<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/ijybl-k1p.css';
import '../../css/u/uh6a78blk.css';
import '../../css/z/z_02kkxdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ijybl-k1p"/><path class="uh6a78blk wm-a"/><path class="z_02kkxdd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:book-open-check-duo" {...props}></Icon>
