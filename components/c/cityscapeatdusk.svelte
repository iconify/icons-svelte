<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcwvm_w5y.css';
import '../../css/r/rebtmz_8a.css';
import '../../css/c/cdjz1qbpw.css';
import '../../css/i/issw8ybpq.css';
import '../../css/h/hi90qgeed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dcwvm_w5y"/><path class="rebtmz_8a"/><path class="cdjz1qbpw"/><path class="issw8ybpq"/><path class="hi90qgeed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:cityscapeatdusk" {...props}></Icon>
