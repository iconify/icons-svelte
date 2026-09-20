<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hw-5j8edp.css';
import '../../css/e/e0w1x5v0y.css';
import '../../css/i/iucnxxyud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hw-5j8edp"/><path class="e0w1x5v0y"/><path class="iucnxxyud"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:gallery-favourite-line-duotone" {...props}></Icon>
