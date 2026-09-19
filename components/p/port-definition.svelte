<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7m4zg46k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e7m4zg46k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:port-definition" {...props}></Icon>
