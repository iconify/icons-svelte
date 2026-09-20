<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/um8oggvox.css';
import '../../css/v/vfsj_cb5a.css';
import '../../css/c/c2nnz_bgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="um8oggvox"/><path class="vfsj_cb5a"/><path class="c2nnz_bgd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:box" {...props}></Icon>
