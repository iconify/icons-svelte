<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btikh_bkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="btikh_bkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:google-play-line" {...props}></Icon>
