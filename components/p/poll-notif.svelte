<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/uw11hvb1q.css';
import '../../css/s/slc920y5k.css';
import '../../css/z/zy99p2e9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="uw11hvb1q"/><path class="slc920y5k"/><path class="zy99p2e9n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:poll-notif" {...props}></Icon>
