<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfpjugbvy.css';
import '../../css/z/zrlwepbcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vfpjugbvy"/><path class="zrlwepbcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-leaf-48-bold" {...props}></Icon>
