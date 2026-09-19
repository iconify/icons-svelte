<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zgisvlbog.css';
import '../../css/z/zvg2rktig.css';
import '../../css/v/v_9vh15ie.css';
import '../../css/j/j85imv7kt.css';
import '../../css/s/s50fz_25z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zgisvlbog"/><path class="zvg2rktig"/><path class="v_9vh15ie"/><path class="j85imv7kt"/><path class="s50fz_25z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:no-internet" {...props}></Icon>
