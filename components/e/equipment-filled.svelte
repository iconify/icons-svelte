<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gam_9d_az.css';
import '../../css/l/lqted7wxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gam_9d_az"/><path clip-rule="evenodd" class="lqted7wxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:equipment-filled" {...props}></Icon>
