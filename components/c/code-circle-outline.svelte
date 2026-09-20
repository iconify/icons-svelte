<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/ky_c7b80d.css';
import '../../css/n/nlm_cm0qu.css';
import '../../css/f/f_ps57bze.css';
import '../../css/s/se_om3jvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ky_c7b80d"/><path class="nlm_cm0qu"/><path class="f_ps57bze"/><path clip-rule="evenodd" class="se_om3jvd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:code-circle-outline" {...props}></Icon>
