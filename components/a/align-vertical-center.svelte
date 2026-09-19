<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gx8y2ds-k.css';
import '../../css/q/q0m24db3d.css';
import '../../css/i/idhaus_4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gx8y2ds-k"><path class="q0m24db3d"/><path class="idhaus_4a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:align-vertical-center" {...props}></Icon>
