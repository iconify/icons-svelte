<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n9m_vhdwt.css';
import '../../css/b/beosq2b5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="n9m_vhdwt"/><path class="beosq2b5r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:moon-duotone" {...props}></Icon>
