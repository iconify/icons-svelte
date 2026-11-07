<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gt4erfbgl.css';
import '../../css/o/o8houvrgo.css';
import '../../css/m/mijy_4gbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gt4erfbgl"/><path class="o8houvrgo"/><path class="mijy_4gbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:round-double-alt-arrow-left-bold-duotone" {...props}></Icon>
