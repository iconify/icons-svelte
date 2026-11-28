<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-5yz33-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-5yz33-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:gamepad-x" {...props}></Icon>
