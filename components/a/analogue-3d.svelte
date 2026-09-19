<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfr3i41sx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yfr3i41sx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:analogue-3d" {...props}></Icon>
