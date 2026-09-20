<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/soe3d3biv.css';
import '../../css/o/ouvk3bb1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="soe3d3biv"/><path class="ouvk3bb1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:nintendo-switch-line" {...props}></Icon>
