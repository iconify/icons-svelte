<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/k_qjhvpku.css';
import '../../css/g/gwzcxibji.css';
import '../../css/u/u9qv1uges.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="k_qjhvpku"/><path class="gwzcxibji"/><path class="u9qv1uges"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:move-circle-outline" {...props}></Icon>
