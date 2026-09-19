<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_9jp5bhq.css';
import '../../css/y/yszbrkbna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s_9jp5bhq"/><path class="yszbrkbna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-unlocked" {...props}></Icon>
