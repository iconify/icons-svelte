<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sahvilbsv.css';
import '../../css/q/qwfd1bbze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sahvilbsv"/><path class="qwfd1bbze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:cspell" {...props}></Icon>
