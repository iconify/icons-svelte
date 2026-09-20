<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in1dviszv.css';
import '../../css/t/tfjq_misc.css';
import '../../css/w/w04x9sayj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="in1dviszv"><path class="tfjq_misc"/><path class="w04x9sayj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:menu-board" {...props}></Icon>
