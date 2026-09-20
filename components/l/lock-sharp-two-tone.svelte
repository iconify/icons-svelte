<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/m/m97iylbud.css';
import '../../css/f/f1l1-0h6y.css';
import '../../css/k/k8te4qbon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="m97iylbud"/><path class="f1l1-0h6y"/><path class="k8te4qbon"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:lock-sharp-two-tone" {...props}></Icon>
