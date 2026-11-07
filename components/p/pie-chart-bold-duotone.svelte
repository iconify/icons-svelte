<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hw6cz2bya.css';
import '../../css/g/gussmibdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hw6cz2bya"/><path class="gussmibdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pie-chart-bold-duotone" {...props}></Icon>
