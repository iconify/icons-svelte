<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9xq4ewmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q9xq4ewmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:draw-io" {...props}></Icon>
