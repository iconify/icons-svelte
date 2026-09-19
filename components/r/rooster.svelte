<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f43n_498d.css';
import '../../css/r/r_yzpyu7i.css';
import '../../css/u/u9-gi0b-r.css';
import '../../css/i/i2snpo6py.css';
import '../../css/x/xl3huwb-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f43n_498d"/><path class="r_yzpyu7i"/><path class="u9-gi0b-r"/><path class="i2snpo6py"/><path class="xl3huwb-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:rooster" {...props}></Icon>
