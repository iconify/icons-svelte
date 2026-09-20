<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/shu3xdl9q.css';
import '../../css/j/j-hctd9nb.css';
import '../../css/f/fo4ccr_rl.css';
import '../../css/u/u2x12mb1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="shu3xdl9q"/><path class="j-hctd9nb"/><path class="fo4ccr_rl"/><path class="u2x12mb1l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:play-circle-stroke" {...props}></Icon>
