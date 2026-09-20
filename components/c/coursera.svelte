<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rl3b5mb1m.css';
import '../../css/e/evze903ec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="rl3b5mb1m"/><path class="evze903ec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:coursera" {...props}></Icon>
