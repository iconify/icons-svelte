<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/ip_hlzfry.css';
import '../../css/k/ky_c7b80d.css';
import '../../css/b/b_gmwtrte.css';
import '../../css/u/u5bqo67kp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ip_hlzfry"/><path class="ky_c7b80d"/><path class="b_gmwtrte"/><path clip-rule="evenodd" class="u5bqo67kp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:code-square-outline" {...props}></Icon>
