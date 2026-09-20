<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfduxkh2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tfduxkh2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:amusement-park-castle" {...props}></Icon>
