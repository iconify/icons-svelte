<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/lv7cpbc3u.css';
import '../../css/d/df-j23bjo.css';
import '../../css/s/spumvty-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lv7cpbc3u"/><path class="df-j23bjo"/><path class="spumvty-n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:mail-receive-02" {...props}></Icon>
