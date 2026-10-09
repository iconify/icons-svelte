<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxik2jbrv.css';
import '../../css/b/b4orwhbsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zxik2jbrv"/><path class="b4orwhbsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:draught-proofing-48" {...props}></Icon>
