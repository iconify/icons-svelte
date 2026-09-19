<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-01x7gco.css';
import '../../css/e/e2rfzjbzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t-01x7gco"/><path class="e2rfzjbzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:media-library" {...props}></Icon>
