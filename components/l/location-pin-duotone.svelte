<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/p-8vtntsb.css';
import '../../css/j/jwa0htbml.css';
import '../../css/g/gs1m2fbso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="p-8vtntsb"/><path class="jwa0htbml"/><path class="gs1m2fbso"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:location-pin-duotone" {...props}></Icon>
