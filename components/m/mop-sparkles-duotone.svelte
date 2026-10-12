<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/a83w9s79w.css';
import '../../css/q/q7dxu21ku.css';
import '../../css/y/ymeccpebe.css';
import '../../css/g/gjg0c_wep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="a83w9s79w"/><path class="q7dxu21ku"/><path class="ymeccpebe"/><path class="gjg0c_wep"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mop-sparkles-duotone" {...props}></Icon>
