<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/p/pn2ogq_7k.css';
import '../../css/u/uzjbj8bwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="bi12bsetm"><path class="pn2ogq_7k"/><path class="uzjbj8bwh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:computer-camera-line" {...props}></Icon>
