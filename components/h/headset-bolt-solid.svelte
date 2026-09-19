<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/i/inkjmjhqc.css';
import '../../css/g/gr6bpbbmd.css';
import '../../css/r/rfyy1zshr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="inkjmjhqc"/><path class="gr6bpbbmd"/><path class="rfyy1zshr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:headset-bolt-solid" {...props}></Icon>
