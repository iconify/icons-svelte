<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cq0r3bb7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="cq0r3bb7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:museum-14" {...props}></Icon>
