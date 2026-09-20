<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/av_zmzb8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="av_zmzb8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:email-arrow-left-outline" {...props}></Icon>
