<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nqmqffbvv.css';
import '../../css/q/qmpj-ib3u.css';
import '../../css/d/dytwysbcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="nqmqffbvv"/><path clip-rule="evenodd" class="qmpj-ib3u"/><path class="dytwysbcm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:gamepad-low-duotone" {...props}></Icon>
