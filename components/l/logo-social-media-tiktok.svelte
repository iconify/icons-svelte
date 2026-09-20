<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5jhss4ab.css';
import '../../css/l/lypy48boz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z5jhss4ab"/><path class="lypy48boz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:logo-social-media-tiktok" {...props}></Icon>
