<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aw9rmcz9o.css';
import '../../css/m/m4l6-obyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aw9rmcz9o"/><path class="m4l6-obyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:at-1x1" {...props}></Icon>
