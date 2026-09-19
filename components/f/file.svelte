<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/h/hky7yeb8h.css';
import '../../css/m/mfgm_vuzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hky7yeb8h"/><path class="mfgm_vuzq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:file" {...props}></Icon>
