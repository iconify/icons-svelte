<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sh4l7dhqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sh4l7dhqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nordvpn" {...props}></Icon>
