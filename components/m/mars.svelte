<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/w/w0v5p4b8e.css';
import '../../css/v/vd7gt8b1z.css';
import '../../css/u/unie4db7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="w0v5p4b8e"/><path class="vd7gt8b1z"/><path class="unie4db7z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:mars" {...props}></Icon>
