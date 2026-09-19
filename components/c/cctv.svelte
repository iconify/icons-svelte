<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/a/a2arncpdg.css';
import '../../css/y/ypq9i8bvk.css';
import '../../css/j/j1d-3tb9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="a2arncpdg"/><path class="ypq9i8bvk"/><path class="j1d-3tb9r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cctv" {...props}></Icon>
