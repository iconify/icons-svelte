<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmibc4bxr.css';
import '../../css/i/i5t49dnmi.css';
import '../../css/n/n-4-una-s.css';
import '../../css/c/cbjdd2zsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="nmibc4bxr"/><path class="i5t49dnmi"/><path class="n-4-una-s"/><path class="cbjdd2zsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:nepal" {...props}></Icon>
