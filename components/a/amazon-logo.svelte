<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6ogabrpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w6ogabrpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:amazon-logo" {...props}></Icon>
