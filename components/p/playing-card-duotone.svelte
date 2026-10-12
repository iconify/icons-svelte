<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/yrn3nmbns.css';
import '../../css/l/l1p3q2bay.css';
import '../../css/l/l-fwh23rz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="yrn3nmbns"/><path class="l1p3q2bay"/><path class="l-fwh23rz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:playing-card-duotone" {...props}></Icon>
