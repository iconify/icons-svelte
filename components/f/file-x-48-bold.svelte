<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdos38jip.css';
import '../../css/r/r7ul0pb7v.css';
import '../../css/h/h_6x60xma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pdos38jip"/><path class="r7ul0pb7v"/><path class="h_6x60xma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:file-x-48-bold" {...props}></Icon>
