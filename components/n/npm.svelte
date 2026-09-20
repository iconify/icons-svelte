<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xdl5stb6w.css';
import '../../css/d/dekp46byi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><rect class="xdl5stb6w"/><path class="dekp46byi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:npm" {...props}></Icon>
