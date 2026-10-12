<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wi3tu6byw.css';
import '../../css/u/uzmwkhbts.css';
import '../../css/a/ajs_333_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wi3tu6byw"/><path class="uzmwkhbts"/><path clip-rule="evenodd" class="ajs_333_f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:monitor-play-duotone" {...props}></Icon>
