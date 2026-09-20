<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkvyz5baw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="tkvyz5baw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:glasses" {...props}></Icon>
