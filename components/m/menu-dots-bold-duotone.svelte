<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxgoffwmm.css';
import '../../css/y/ywojd67ji.css';
import '../../css/k/khsdxy-1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gxgoffwmm"/><path class="ywojd67ji"/><path class="khsdxy-1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:menu-dots-bold-duotone" {...props}></Icon>
