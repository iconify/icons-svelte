<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/boof0ab7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="boof0ab7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:pentagon-outline" {...props}></Icon>
