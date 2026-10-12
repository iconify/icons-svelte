<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wb4hvmmhg.css';
import '../../css/m/mrseusbbp.css';
import '../../css/n/n7-rbcc3s.css';
import '../../css/o/ocgaxn_is.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wb4hvmmhg"/><path class="mrseusbbp"/><path class="n7-rbcc3s"/><path class="ocgaxn_is"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:medal-duotone" {...props}></Icon>
