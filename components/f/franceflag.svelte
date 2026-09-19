<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3ep-0b7w.css';
import '../../css/r/rcci-d4wx.css';
import '../../css/b/b197rfn0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y3ep-0b7w"/><path class="rcci-d4wx"/><path class="b197rfn0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:franceflag" {...props}></Icon>
