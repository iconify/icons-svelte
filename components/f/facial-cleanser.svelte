<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/t/tn0h24bih.css';
import '../../css/t/ti1fmsbsz.css';
import '../../css/h/h8xgiibmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path class="tn0h24bih"/><path class="ti1fmsbsz"/><path class="h8xgiibmi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:facial-cleanser" {...props}></Icon>
