<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cvtzdzbdn.css';
import '../../css/a/alhb85b0y.css';
import '../../css/r/r3bq5ybxj.css';
import '../../css/q/qdpsikbik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="cvtzdzbdn"/><rect class="alhb85b0y"/><circle class="r3bq5ybxj"/><path class="qdpsikbik"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:camera2" {...props}></Icon>
