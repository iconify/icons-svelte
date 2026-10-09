<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gn8iwfgiz.css';
import '../../css/e/ey8dz-b1l.css';
import '../../css/y/y1198cbkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gn8iwfgiz"/><path class="ey8dz-b1l"/><path class="y1198cbkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:refresh-ccw-48" {...props}></Icon>
