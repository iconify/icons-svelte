<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdv6r3b5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="qdv6r3b5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:column-vertical-section" {...props}></Icon>
