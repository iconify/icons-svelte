<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/kfp3c8bsz.css';
import '../../css/c/ct5w8kbba.css';
import '../../css/t/tkrpcdone.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="kfp3c8bsz"/><path class="ct5w8kbba"/><path class="tkrpcdone"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:file-sparkles" {...props}></Icon>
