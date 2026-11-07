<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bun2tveba.css';
import '../../css/j/jkjtg1bfn.css';
import '../../css/v/vf4j3wl2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bun2tveba"/><path class="jkjtg1bfn"/><path class="vf4j3wl2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cash-out-bold" {...props}></Icon>
