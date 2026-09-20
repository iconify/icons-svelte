<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njnmu2p-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="njnmu2p-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:basic-arrows-right" {...props}></Icon>
