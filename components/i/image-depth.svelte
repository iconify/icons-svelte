<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bkaq4tblo.css';
import '../../css/p/pny223f3z.css';
import '../../css/s/smdysmmqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bkaq4tblo"/><path class="pny223f3z"/><path class="smdysmmqk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:image-depth" {...props}></Icon>
