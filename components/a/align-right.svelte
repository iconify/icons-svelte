<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7ys7fbjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l7ys7fbjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:align-right" {...props}></Icon>
