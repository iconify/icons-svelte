<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/te0_z2frq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="te0_z2frq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:arrow-circle-left" {...props}></Icon>
