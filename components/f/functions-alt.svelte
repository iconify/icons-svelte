<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fc1e6ys7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fc1e6ys7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:functions-alt" {...props}></Icon>
