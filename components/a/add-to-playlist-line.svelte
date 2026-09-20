<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixphqr3ei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixphqr3ei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:add-to-playlist-line" {...props}></Icon>
