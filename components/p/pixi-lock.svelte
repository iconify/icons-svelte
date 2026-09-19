<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avwrpqfiu.css';
import '../../css/d/dw535lrsr.css';
import '../../css/b/btgs09vbq.css';
import '../../css/p/p1mqhfd7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="avwrpqfiu"/><path class="dw535lrsr"/><path class="btgs09vbq"/><path class="p1mqhfd7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:pixi-lock" {...props}></Icon>
