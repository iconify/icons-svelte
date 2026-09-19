<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qm77mwb7x.css';
import '../../css/r/rjes9k1zx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="qm77mwb7x"/><path class="rjes9k1zx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:cube-3d" {...props}></Icon>
