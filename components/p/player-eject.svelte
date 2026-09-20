<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nu28otbts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nu28otbts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:player-eject" {...props}></Icon>
