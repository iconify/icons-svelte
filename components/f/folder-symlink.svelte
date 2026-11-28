<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/tgy8uab8v.css';
import '../../css/h/hea1y1b2z.css';
import '../../css/e/e-ope2q4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="tgy8uab8v"/><path class="hea1y1b2z"/><path class="e-ope2q4f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:folder-symlink" {...props}></Icon>
