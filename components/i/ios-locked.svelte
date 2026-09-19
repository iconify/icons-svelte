<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x16rdgb4k.css';
import '../../css/s/s_9jp5bhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x16rdgb4k"/><path class="s_9jp5bhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-locked" {...props}></Icon>
