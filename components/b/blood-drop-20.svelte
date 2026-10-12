<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_vodpr_t.css';
import '../../css/z/z0mp7-b9d.css';
import '../../css/l/l724hebta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z_vodpr_t"/><path class="z0mp7-b9d"/><path class="l724hebta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:blood-drop-20" {...props}></Icon>
