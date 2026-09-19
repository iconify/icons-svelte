<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxp94h8ew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nxp94h8ew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:moon-solid" {...props}></Icon>
