<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uw4fykdpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uw4fykdpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:gotomeeting" {...props}></Icon>
