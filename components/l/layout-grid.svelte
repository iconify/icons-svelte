<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/sdnn0rbfr.css';
import '../../css/q/qkgcgxv2f.css';
import '../../css/k/kdqnsi7wk.css';
import '../../css/q/qmeb7ubyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="sdnn0rbfr"/><path class="qkgcgxv2f"/><path class="kdqnsi7wk"/><path class="qmeb7ubyc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:layout-grid" {...props}></Icon>
