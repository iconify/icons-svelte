<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvggpac7z.css';
import '../../css/s/sjprxildg.css';
import '../../css/o/o0i8t4b7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wvggpac7z"/><path class="sjprxildg"/><path class="o0i8t4b7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-meter-48" {...props}></Icon>
