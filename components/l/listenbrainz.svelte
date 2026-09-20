<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0q0qobhx.css';
import '../../css/x/xoum1hbfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a0q0qobhx"/><path class="xoum1hbfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:listenbrainz" {...props}></Icon>
