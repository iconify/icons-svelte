<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in1dviszv.css';
import '../../css/v/vgba34o3n.css';
import '../../css/h/hasbc2bzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="in1dviszv"><path class="vgba34o3n"/><path class="hasbc2bzw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:folder-open3" {...props}></Icon>
