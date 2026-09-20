<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv-9ckosh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gv-9ckosh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:apachekylin" {...props}></Icon>
