<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7brlpbnx.css';
import '../../css/x/xz4txmb-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b7brlpbnx"/><path class="xz4txmb-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-shuffle" {...props}></Icon>
