<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x30e65b2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="x30e65b2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:chevron-left-end-6" {...props}></Icon>
