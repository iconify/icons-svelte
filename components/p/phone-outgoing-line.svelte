<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcl_b78rm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dcl_b78rm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:phone-outgoing-line" {...props}></Icon>
