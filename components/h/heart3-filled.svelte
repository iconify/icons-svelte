<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iekxtii2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iekxtii2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:heart3-filled" {...props}></Icon>
