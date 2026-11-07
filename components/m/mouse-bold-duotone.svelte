<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1vz89b1w.css';
import '../../css/z/z5dw2mc_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r1vz89b1w"/><path class="z5dw2mc_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:mouse-bold-duotone" {...props}></Icon>
