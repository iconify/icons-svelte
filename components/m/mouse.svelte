<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxf00_bft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mxf00_bft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:mouse" {...props}></Icon>
