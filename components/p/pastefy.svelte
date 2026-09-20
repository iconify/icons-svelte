<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8z18xbtt.css';
import '../../css/j/j1680wbis.css';
import '../../css/a/aavykeq3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n8z18xbtt"/><path class="j1680wbis"/><path class="aavykeq3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pastefy" {...props}></Icon>
