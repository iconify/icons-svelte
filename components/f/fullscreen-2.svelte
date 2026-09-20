<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igpt2fgqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="igpt2fgqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:fullscreen-2" {...props}></Icon>
