<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ij52glb-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ij52glb-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:male-sign" {...props}></Icon>
