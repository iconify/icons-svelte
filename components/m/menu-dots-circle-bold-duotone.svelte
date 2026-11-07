<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnb90nbxf.css';
import '../../css/q/qazb7jbeb.css';
import '../../css/y/y4zl2mbio.css';
import '../../css/o/o-v99zb0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnb90nbxf"/><path class="qazb7jbeb"/><path class="y4zl2mbio"/><path class="o-v99zb0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:menu-dots-circle-bold-duotone" {...props}></Icon>
