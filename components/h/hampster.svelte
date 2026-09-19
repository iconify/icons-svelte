<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cc0c_gq-d.css';
import '../../css/s/sx0qtzbwt.css';
import '../../css/l/l5a55bckk.css';
import '../../css/n/nspmw7h7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cc0c_gq-d"/><path class="sx0qtzbwt"/><path class="l5a55bckk"/><path class="nspmw7h7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:hampster" {...props}></Icon>
