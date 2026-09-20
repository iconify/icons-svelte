<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k5rl6d9jn.css';
import '../../css/e/eof3lkbhp.css';
import '../../css/w/w2qbg1srf.css';
import '../../css/q/qvsov4fod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="k5rl6d9jn"/><path class="eof3lkbhp"/><path class="w2qbg1srf"/><path class="qvsov4fod"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:guitar" {...props}></Icon>
