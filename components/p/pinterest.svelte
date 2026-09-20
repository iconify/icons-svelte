<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl55q5bty.css';
import '../../css/l/lr1-z_9gb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yl55q5bty"/><path class="lr1-z_9gb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pinterest" {...props}></Icon>
