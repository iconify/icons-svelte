<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zn3t6_bmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zn3t6_bmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:habr" {...props}></Icon>
