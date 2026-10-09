<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejaztkbty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ejaztkbty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:homey" {...props}></Icon>
