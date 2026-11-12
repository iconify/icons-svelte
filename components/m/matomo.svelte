<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spf7r7h-h.css';
import '../../css/p/pqi-gtarw.css';
import '../../css/j/joab4p6un.css';
import '../../css/i/i4kk3c25z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="spf7r7h-h"/><circle class="pqi-gtarw"/><circle class="joab4p6un"/><path class="i4kk3c25z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:matomo" {...props}></Icon>
