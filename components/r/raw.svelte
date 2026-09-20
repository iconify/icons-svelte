<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq92o0bks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vq92o0bks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:raw" {...props}></Icon>
