<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o84rn3bvm.css';
import '../../css/n/nbj9xhbai.css';
import '../../css/w/w742qcbke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="o84rn3bvm"/><path class="nbj9xhbai"/><path class="w742qcbke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lidar-48" {...props}></Icon>
