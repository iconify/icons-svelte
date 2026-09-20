<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhm_dub_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vhm_dub_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-video-fill" {...props}></Icon>
