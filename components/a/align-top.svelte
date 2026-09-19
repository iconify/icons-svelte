<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gx8y2ds-k.css';
import '../../css/q/qfh1dz3dh.css';
import '../../css/d/denxdxots.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gx8y2ds-k"><path class="qfh1dz3dh"/><path class="denxdxots"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:align-top" {...props}></Icon>
