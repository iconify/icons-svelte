<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bu16377vq.css';
import '../../css/y/ynooprbfx.css';
import '../../css/r/rmbuj8bce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bu16377vq"/><path class="ynooprbfx"/><path clip-rule="evenodd" class="rmbuj8bce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:calendar-star" {...props}></Icon>
