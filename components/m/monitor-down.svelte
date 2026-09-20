<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/d/dt8nv5bcs.css';
import '../../css/r/r8-cjywgb.css';
import '../../css/h/h7focp4gr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dt8nv5bcs"/><rect class="r8-cjywgb"/><path class="h7focp4gr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:monitor-down" {...props}></Icon>
