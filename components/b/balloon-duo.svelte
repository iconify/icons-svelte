<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/ify3__5xp.css';
import '../../css/k/kqdww1lkr.css';
import '../../css/d/d5kv-1gyk.css';
import '../../css/w/wjjs-ibru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ify3__5xp"/><path class="kqdww1lkr wm-a"/><path class="d5kv-1gyk"/><path class="wjjs-ibru wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:balloon-duo" {...props}></Icon>
