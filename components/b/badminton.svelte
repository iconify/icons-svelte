<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pu2p00rwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pu2p00rwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:badminton" {...props}></Icon>
