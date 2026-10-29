<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/w/w4ztz2btj.css';
import '../../css/k/k1goh-kki.css';
import '../../css/u/uy8yhu9at.css';
import '../../css/y/yui4pigey.css';
import '../../css/o/o-qp5zbng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="w4ztz2btj"/><path class="k1goh-kki wm-a"/><path class="uy8yhu9at wm-a"/><path class="yui4pigey"/><path class="o-qp5zbng wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:files-duo" {...props}></Icon>
