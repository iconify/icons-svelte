<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/netg96bwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="netg96bwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:labview" {...props}></Icon>
