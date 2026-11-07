<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xf4ca1btm.css';
import '../../css/r/r_wkqfbyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xf4ca1btm"/><path class="r_wkqfbyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:body-shape-bold-duotone" {...props}></Icon>
