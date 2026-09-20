<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/h/h7focp4gr.css';
import '../../css/r/r8-cjywgb.css';
import '../../css/m/mpq6rb0rh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h7focp4gr"/><rect class="r8-cjywgb"/><rect class="mpq6rb0rh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:monitor-stop" {...props}></Icon>
