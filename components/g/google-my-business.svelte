<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxz4mvbix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vxz4mvbix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:google-my-business" {...props}></Icon>
