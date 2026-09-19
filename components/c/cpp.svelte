<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvek_hfww.css';
import '../../css/i/inswb7bej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="cvek_hfww"/><path class="inswb7bej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:cpp" {...props}></Icon>
