<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcxgohb4h.css';
import '../../css/x/xbefkzbox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rcxgohb4h"/><path class="xbefkzbox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:quire-ink-dark" {...props}></Icon>
