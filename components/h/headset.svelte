<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpd3_gbnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mpd3_gbnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:headset" {...props}></Icon>
