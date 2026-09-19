<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wsq8muggl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wsq8muggl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:artificial-intelligence-01" {...props}></Icon>
