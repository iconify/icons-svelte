<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxgoffwmm.css';
import '../../css/m/m5-5o8s_j.css';
import '../../css/y/ywojd67ji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gxgoffwmm"/><path class="m5-5o8s_j"/><path class="ywojd67ji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:menu-dots-bold" {...props}></Icon>
