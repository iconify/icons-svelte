<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g87b65bny.css';
import '../../css/t/t8sx1mbrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g87b65bny"/><path class="t8sx1mbrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:logo-social-media-tiktok-circle" {...props}></Icon>
