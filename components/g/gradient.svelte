<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9suhacgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="x9suhacgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:gradient" {...props}></Icon>
