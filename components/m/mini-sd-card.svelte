<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/a/a_ov9vbto.css';
import '../../css/j/jcocdpb8j.css';
import '../../css/i/iwe9abbhf.css';
import '../../css/s/sr6x3ialb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path clip-rule="evenodd" class="a_ov9vbto"/><path class="jcocdpb8j"/><path class="iwe9abbhf"/><path class="sr6x3ialb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:mini-sd-card" {...props}></Icon>
