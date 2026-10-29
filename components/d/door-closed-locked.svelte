<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/goc6or3vc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="goc6or3vc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:door-closed-locked" {...props}></Icon>
