<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/ybqotybcr.css';
import '../../css/g/gf0i1ln3b.css';
import '../../css/u/uaqobub-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ybqotybcr"/><path class="gf0i1ln3b"/><path class="uaqobub-b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:certificate-badge-duotone" {...props}></Icon>
