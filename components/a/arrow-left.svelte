<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebldvkbho.css';
import '../../css/q/q_3cglb4g.css';
import '../../css/d/dxxog678i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="ebldvkbho"/><path class="q_3cglb4g"/><path class="dxxog678i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:arrow-left" {...props}></Icon>
