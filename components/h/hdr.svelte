<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ne2zhwbws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ne2zhwbws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:hdr" {...props}></Icon>
