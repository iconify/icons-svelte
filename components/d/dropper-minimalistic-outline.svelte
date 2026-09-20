<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/x6pve2s3y.css';
import '../../css/s/s5hlx6soy.css';
import '../../css/m/mp5_upgbq.css';
import '../../css/e/e04kqrbnp.css';
import '../../css/l/lr1ofccoy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="x6pve2s3y"/><path class="s5hlx6soy"/><path class="mp5_upgbq"/><path clip-rule="evenodd" class="e04kqrbnp"/><path clip-rule="evenodd" class="lr1ofccoy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:dropper-minimalistic-outline" {...props}></Icon>
