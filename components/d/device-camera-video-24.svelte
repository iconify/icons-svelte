<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymj9h20wk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ymj9h20wk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:device-camera-video-24" {...props}></Icon>
