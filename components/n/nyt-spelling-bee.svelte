<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qedz3ihgl.css';
import '../../css/v/vr-z-kb2v.css';
import '../../css/e/eg9qh-kkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qedz3ihgl"/><ellipse class="vr-z-kb2v"/><path class="eg9qh-kkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nyt-spelling-bee" {...props}></Icon>
