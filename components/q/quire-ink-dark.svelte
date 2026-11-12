<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5p876b5i.css';
import '../../css/v/vwv3t9bhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x5p876b5i"/><path class="vwv3t9bhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:quire-ink-dark" {...props}></Icon>
