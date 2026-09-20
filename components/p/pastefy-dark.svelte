<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dx914upgl.css';
import '../../css/r/rc6--6b0h.css';
import '../../css/w/wmnw5bvdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dx914upgl"/><path class="rc6--6b0h"/><path class="wmnw5bvdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pastefy-dark" {...props}></Icon>
