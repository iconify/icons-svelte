<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/beffpzbxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="beffpzbxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:media-subtitles-unavailable" {...props}></Icon>
