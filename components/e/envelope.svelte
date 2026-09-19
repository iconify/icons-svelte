<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtqmscb8b.css';
import '../../css/y/yujr8pbfe.css';
import '../../css/j/jpvlp2bch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vtqmscb8b"/><path class="yujr8pbfe"/><path class="jpvlp2bch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:envelope" {...props}></Icon>
