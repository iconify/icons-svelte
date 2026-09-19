<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6t-gvgwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="e6t-gvgwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:event" {...props}></Icon>
