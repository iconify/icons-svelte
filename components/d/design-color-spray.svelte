<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zheynwbwf.css';
import '../../css/p/pr7drww8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zheynwbwf"/><path class="pr7drww8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:design-color-spray" {...props}></Icon>
