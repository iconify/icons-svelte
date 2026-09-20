<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9y4dyb1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i9y4dyb1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:logo-social-media-youtube-circle" {...props}></Icon>
