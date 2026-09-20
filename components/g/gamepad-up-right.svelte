<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2511yb0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="q2511yb0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:gamepad-up-right" {...props}></Icon>
