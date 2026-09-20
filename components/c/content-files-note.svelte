<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djkbxwbon.css';
import '../../css/i/imeyubcwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="djkbxwbon"/><path class="imeyubcwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:content-files-note" {...props}></Icon>
