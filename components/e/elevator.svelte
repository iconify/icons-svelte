<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzfeitich.css';
import '../../css/j/jzxguacfp.css';
import '../../css/v/v8s6amb7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="qzfeitich"/><path class="jzxguacfp"/><path class="v8s6amb7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:elevator" {...props}></Icon>
