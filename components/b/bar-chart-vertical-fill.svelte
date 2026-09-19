<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bf_crfbom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="bf_crfbom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:bar-chart-vertical-fill" {...props}></Icon>
