<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvl2pzwmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gvl2pzwmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:insurance-hand-bold" {...props}></Icon>
