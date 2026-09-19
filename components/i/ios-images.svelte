<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnl1p-2gq.css';
import '../../css/l/llymw2wsd.css';
import '../../css/s/slx--zbzd.css';
import '../../css/l/loxcckgkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qnl1p-2gq"/><path class="llymw2wsd"/><path class="slx--zbzd"/><path class="loxcckgkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-images" {...props}></Icon>
