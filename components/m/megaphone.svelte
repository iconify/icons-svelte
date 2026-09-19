<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zskw_mbgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zskw_mbgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:megaphone" {...props}></Icon>
