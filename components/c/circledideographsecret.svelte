<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvnkdr6kn.css';
import '../../css/u/ufqy7fo2b.css';
import '../../css/w/wvnrybc8p.css';
import '../../css/a/azzi7-0in.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="qvnkdr6kn"/><path class="ufqy7fo2b"/><path class="wvnrybc8p"/><path class="azzi7-0in"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:circledideographsecret" {...props}></Icon>
