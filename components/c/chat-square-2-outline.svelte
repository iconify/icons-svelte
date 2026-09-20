<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qq3jwzbiv.css';
import '../../css/l/l_rtxu4wa.css';
import '../../css/i/ia1mkhbft.css';
import '../../css/u/u5bqo67kp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qq3jwzbiv"/><path class="l_rtxu4wa"/><path class="ia1mkhbft"/><path clip-rule="evenodd" class="u5bqo67kp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-square-2-outline" {...props}></Icon>
