<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vi6jplbfg.css';
import '../../css/y/yg3s2lbnw.css';
import '../../css/j/jyzwxfyfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="vi6jplbfg"/><path class="yg3s2lbnw"/><path class="jyzwxfyfe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:gps-fixed-duotone-line" {...props}></Icon>
