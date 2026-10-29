<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/fokpgob2f.css';
import '../../css/u/u5j49objb.css';
import '../../css/q/qzof9nhok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="fokpgob2f"/><path class="u5j49objb wm-a"/><path class="qzof9nhok"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:beef-duo" {...props}></Icon>
