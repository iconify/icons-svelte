<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wz20asb0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wz20asb0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:group-alt-filled" {...props}></Icon>
