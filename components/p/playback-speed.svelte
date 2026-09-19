<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k3_8jwp2c.css';
import '../../css/a/acs8qldpc.css';
import '../../css/b/b29-gmble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="k3_8jwp2c"/><path class="acs8qldpc"/><path class="b29-gmble"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:playback-speed" {...props}></Icon>
