<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yolb2c1_c.css';
import '../../css/r/rvcb4bedk.css';
import '../../css/y/y-7m_e66k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="yolb2c1_c"/><path class="rvcb4bedk"/><path class="y-7m_e66k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:retweet" {...props}></Icon>
