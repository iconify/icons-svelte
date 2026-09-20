<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5ibnw1da.css';
import '../../css/y/yooxxnacr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r5ibnw1da"/><path class="yooxxnacr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:logo-social-media-dropbox" {...props}></Icon>
