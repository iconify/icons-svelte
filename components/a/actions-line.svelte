<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddvgu8bvv.css';
import '../../css/d/dawcsab1j.css';
import '../../css/d/dv9bu8b_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ddvgu8bvv"><path class="dawcsab1j"/><path class="dv9bu8b_h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:actions-line" {...props}></Icon>
